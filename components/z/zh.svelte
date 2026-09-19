<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/w/wj-7246uw.css';
import '../../css/n/n6_r6fbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsZh0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsZh0)"><path class="wj-7246uw"/><path class="n6_r6fbmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:zh" {...props}></Icon>
