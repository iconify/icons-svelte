<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj1qj2dgf.css';
import '../../css/x/xdvevhb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj1qj2dgf"/><path class="xdvevhb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:view-board" {...props}></Icon>
