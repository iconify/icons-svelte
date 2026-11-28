<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9_w5wtle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9_w5wtle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-split-bottom-right-solid" {...props}></Icon>
