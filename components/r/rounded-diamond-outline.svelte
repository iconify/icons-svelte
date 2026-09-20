<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3d7irbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n3d7irbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-diamond-outline" {...props}></Icon>
