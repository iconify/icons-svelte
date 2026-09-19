<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqkbldb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zqkbldb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:shopping-bags" {...props}></Icon>
