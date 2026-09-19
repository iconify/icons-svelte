<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am-lkyrde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am-lkyrde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sitemap-filled" {...props}></Icon>
