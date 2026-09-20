<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9ydt-b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x9ydt-b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tennessee-with-capital-star" {...props}></Icon>
