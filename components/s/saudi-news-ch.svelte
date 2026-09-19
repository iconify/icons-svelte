<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7c-acb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7c-acb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:saudi-news-ch" {...props}></Icon>
