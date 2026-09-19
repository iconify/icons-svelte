<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn6jciybe.css';
import '../../css/n/nxbv23bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vn6jciybe"/><path class="nxbv23bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rss" {...props}></Icon>
