<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of_ijc5ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="of_ijc5ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:white-medium-small-square" {...props}></Icon>
