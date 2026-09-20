<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr5g377_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr5g377_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sitemap-off" {...props}></Icon>
