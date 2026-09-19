<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kje457rsc.css';
import '../../css/c/ckdfspy3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kje457rsc"/><path class="ckdfspy3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:view-timeline" {...props}></Icon>
