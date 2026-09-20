<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-39dzkxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-39dzkxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:upload-off" {...props}></Icon>
