<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8yhflb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d8yhflb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:rss-feed-tag-solid" {...props}></Icon>
