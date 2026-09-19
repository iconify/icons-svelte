<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq6p5-u8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zq6p5-u8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:snaptodot" {...props}></Icon>
