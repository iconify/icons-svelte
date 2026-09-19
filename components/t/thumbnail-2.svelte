<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daw47cb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="daw47cb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thumbnail-2" {...props}></Icon>
