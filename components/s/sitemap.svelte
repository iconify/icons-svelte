<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic8oehl0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic8oehl0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:sitemap" {...props}></Icon>
