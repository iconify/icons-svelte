<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3u0_wbck.css';
import '../../css/y/yalmj9bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3u0_wbck"/><path class="yalmj9bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:speaker" {...props}></Icon>
