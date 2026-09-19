<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un5oheb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="un5oheb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:t-shirt" {...props}></Icon>
