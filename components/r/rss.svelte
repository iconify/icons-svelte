<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bljn7e6ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bljn7e6ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:rss" {...props}></Icon>
