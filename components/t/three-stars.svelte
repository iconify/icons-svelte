<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcq-3vtmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcq-3vtmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:three-stars" {...props}></Icon>
