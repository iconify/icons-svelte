<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa7ad-bhf.css';
import '../../css/u/uf38hibyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wa7ad-bhf"/><path class="uf38hibyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:star" {...props}></Icon>
