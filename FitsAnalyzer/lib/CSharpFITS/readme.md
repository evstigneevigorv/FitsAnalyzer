This repo is a fork of http://vo.iucaa.ernet.in/~voi/CSharpFITS.html who unfortunately do not have a github repo of their own. This fork is modernizing the code base.  It has been updated to .net to 4.0, Visual Studio to 2013 and nUnit to 3.x.

	CSharpFITS package is a pure C# .NET port of Tom McGlynn's nom.tam.fits Java package. It provides native C# support for reading and writing FITS files.

	The CSharpFITS package  was initially ported by Samuel Carliles. The development of this new version of CSharpFITS is undertaken by VO-I.
	


Note: This document was begun from above and at nom.tam.fits site except that examples are now in C#
    
 	

    BasicHDU h = Fits.makeHDU(x);
        if (h != null) 
        {
        {
    {
    
    {
    }
    // Now after TCX
    String key = iter.MoveNext().getKey();   // Get the key
    {
    Header h = Header.ReadHeader(bf);
    HeaderCard hnew= new HeaderCard("NAXIS",  naxes - 1,"this is  header card with naxes");
    float[] line = new float[h.DataSize];
    for (int i = 0; i < lastAxis; i += 1)


    ... these arrays have the same dimensions ...
    Object[] cols =new Object[] { realCol, intCol, longCol, doubleCol, strCol };
    

    
	BufferedFile bf = new BufferedFile("outputfile", "rw");
    bf.Dispose();
    
    data.SetColumn(0, f2);
    f1 = new float[] { 3.14159f };
    Object[] row = new Object[5];

    bf.Dispose();


    
and others
    stream.Write(data);