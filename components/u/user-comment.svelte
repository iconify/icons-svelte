<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcyd0w18b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="kcyd0w18b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:user-comment" {...props}></Icon>
