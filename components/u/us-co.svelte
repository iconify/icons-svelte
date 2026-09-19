<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/w/w5xyq8egd.css';
import '../../css/i/i08mdbbdr.css';
import '../../css/l/letow6vpi.css';
import '../../css/y/yttteebpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="w5xyq8egd"/><path class="i08mdbbdr"/><path class="letow6vpi"/><circle class="yttteebpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:us-co" {...props}></Icon>
