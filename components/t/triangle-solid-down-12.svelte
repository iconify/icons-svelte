<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlo5nub7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zlo5nub7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:triangle-solid-down-12" {...props}></Icon>
