<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvhra_bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvhra_bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:signpost-round" {...props}></Icon>
