<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmmnkib2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dmmnkib2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:shamrock" {...props}></Icon>
