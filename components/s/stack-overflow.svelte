<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr7b1pcrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fr7b1pcrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:stack-overflow" {...props}></Icon>
