<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd4v7obem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hd4v7obem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-eighth-notes" {...props}></Icon>
