<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-n-k1c4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="k-n-k1c4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:sitemap" {...props}></Icon>
