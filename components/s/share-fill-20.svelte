<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrff5xbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rrff5xbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:share-fill-20" {...props}></Icon>
