<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-qtrrb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y-qtrrb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:share-alt2" {...props}></Icon>
