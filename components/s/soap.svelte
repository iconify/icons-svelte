<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4iaj5kvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c4iaj5kvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:soap" {...props}></Icon>
