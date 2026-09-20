<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hienlub7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hienlub7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-vertical-rotate-counterclockwise" {...props}></Icon>
