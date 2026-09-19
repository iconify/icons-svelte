<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_b-7fbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o_b-7fbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-left-stroke-16" {...props}></Icon>
