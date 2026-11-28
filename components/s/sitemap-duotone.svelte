<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5p742bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary w5p742bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sitemap-duotone" {...props}></Icon>
