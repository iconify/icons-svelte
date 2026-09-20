<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkv5dq48z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkv5dq48z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sun-fall-filled" {...props}></Icon>
