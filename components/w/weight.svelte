<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bimb9pjdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bimb9pjdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:weight" {...props}></Icon>
