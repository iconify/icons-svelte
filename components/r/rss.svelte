<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvi1ht2vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="zvi1ht2vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:rss" {...props}></Icon>
