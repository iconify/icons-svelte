<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/w/w7mzmcwfz.css';
import '../../css/m/mf42w9b3n.css';
import '../../css/z/zx8xtccho.css';
import '../../css/s/s06r0_b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="w7mzmcwfz"/><path class="mf42w9b3n"/><path class="zx8xtccho"/><path class="s06r0_b1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:us-az" {...props}></Icon>
