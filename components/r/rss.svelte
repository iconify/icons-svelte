<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awyp7-bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awyp7-bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:rss" {...props}></Icon>
