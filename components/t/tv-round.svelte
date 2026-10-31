<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awpbezbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awpbezbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tv-round" {...props}></Icon>
