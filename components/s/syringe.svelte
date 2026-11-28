<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd8ib77jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd8ib77jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:syringe" {...props}></Icon>
