<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0z39514c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b0z39514c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:star-half" {...props}></Icon>
