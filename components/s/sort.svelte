<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx03b9a_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zx03b9a_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:sort" {...props}></Icon>
