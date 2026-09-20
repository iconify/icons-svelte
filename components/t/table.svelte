<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe0fey4fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe0fey4fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:table" {...props}></Icon>
