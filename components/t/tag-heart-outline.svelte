<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceqzzwbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceqzzwbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-heart-outline" {...props}></Icon>
