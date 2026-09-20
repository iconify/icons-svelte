<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl9z38o3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl9z38o3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seal-variant" {...props}></Icon>
