# Python script to create mass accretion rates, halo masses,
# NFW concentrations, sigma variance fluctuations for haloes
# of any mass at any redshift for any flat LCDM cosmology based
# on Correa et al 2015 a,b,c

# To acquire use `pip install commah' or clone the repository
# Requires scipy, numpy, cosmolopy

# To run:
# import commah
# Output = commah.run('WMAP5', zi = 0., Mi=[1e12], z=[1.,2.,3.])
# Output is a data structure with initial redshift 'zi',
# initial halo mass 'Mi', final redshift 'z', final halo mass 'Mz',
# accretion rate 'dMdt', concentration 'c', mass variance 'sig',
# fluctuation parameter 'nu'

# User inputs the cosmology (either as a dict or named example
# provided in the cosmology_list.py file, such as 'WMAP5')
# and redshift / mass of halo (can be array/list/single entry)
# and desired output redshifts (can leave as blank and by default
# the variables are given for the starting redshift) can be
# array / list / single entry

# For more command examples or plot examples see:
# from commah import examples
# examples.runcommand()
#
# or
#
# examples.plotcommand()
