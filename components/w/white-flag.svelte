<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rah4qbcvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rah4qbcvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:white-flag" {...props}></Icon>
