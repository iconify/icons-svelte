<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/p/pfmrfyugg.css';
import '../../css/e/e7nec2b-k.css';
import '../../css/q/q7fxrfbxx.css';
import '../../css/h/h1zxe6c2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="pfmrfyugg"/><path class="e7nec2b-k"/><path class="q7fxrfbxx"/><path class="h1zxe6c2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:us-betsy-ross" {...props}></Icon>
