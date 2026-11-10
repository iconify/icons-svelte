<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk-_17g4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk-_17g4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sitemap-plus" {...props}></Icon>
