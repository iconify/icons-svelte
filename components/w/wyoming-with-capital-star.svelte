<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daj8xub0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="daj8xub0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wyoming-with-capital-star" {...props}></Icon>
