<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f96_kccde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f96_kccde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skew-decrease" {...props}></Icon>
