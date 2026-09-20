<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csjmgi5ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csjmgi5ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:vimeo" {...props}></Icon>
