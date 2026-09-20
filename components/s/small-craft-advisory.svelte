<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3rfekbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="k3rfekbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:small-craft-advisory" {...props}></Icon>
