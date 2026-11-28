<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lysg2jqtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lysg2jqtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trash-can-solid" {...props}></Icon>
