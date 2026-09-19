<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/r/rklh0zdmu.css';
import '../../css/p/pab7pn29i.css';
import '../../css/w/wu7k8_ixa.css';
import '../../css/h/h3shtbc9x.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRMoMLc1A"><g class="gopnm44um"><rect class="rklh0zdmu"/><path class="pab7pn29i"/><path class="wu7k8_ixa"/><path class="h3shtbc9x"/></g></mask></defs><path mask="url(#SVGRMoMLc1A)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:schedule" {...props}></Icon>
