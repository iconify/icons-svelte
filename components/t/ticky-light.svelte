<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-4uxpbxq.css';
import '../../css/c/cjzwyi8ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c-4uxpbxq"/><path class="cjzwyi8ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ticky-light" {...props}></Icon>
