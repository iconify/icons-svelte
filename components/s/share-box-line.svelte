<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0cvg57jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0cvg57jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-box-line" {...props}></Icon>
