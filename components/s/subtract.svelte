<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba7791_9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ba7791_9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:subtract" {...props}></Icon>
