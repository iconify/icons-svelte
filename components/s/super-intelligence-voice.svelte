<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm6wsvb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm6wsvb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:super-intelligence-voice" {...props}></Icon>
