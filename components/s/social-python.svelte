<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov02yvbiu.css';
import '../../css/w/w19t2zbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ov02yvbiu"/><path class="w19t2zbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-python" {...props}></Icon>
