<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq0b-nbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq0b-nbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:volume-medium" {...props}></Icon>
