<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzh6otbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uzh6otbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sun-behind-rain-cloud" {...props}></Icon>
