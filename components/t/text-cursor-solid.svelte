<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcshijoom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcshijoom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:text-cursor-solid" {...props}></Icon>
