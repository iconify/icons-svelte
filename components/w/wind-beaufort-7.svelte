<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1wv2ynnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="a1wv2ynnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-7" {...props}></Icon>
