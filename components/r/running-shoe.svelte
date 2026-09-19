<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1v9r1bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s1v9r1bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:running-shoe" {...props}></Icon>
