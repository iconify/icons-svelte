<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyhpkdsso.css';
import '../../css/x/xf-7ownph.css';
import '../../css/f/fhmm_kygi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyhpkdsso"/><path class="xf-7ownph"/><path class="fhmm_kygi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-horizontal-bold" {...props}></Icon>
