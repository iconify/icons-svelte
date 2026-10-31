<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_b7j0aqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_b7j0aqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:running-fill-round" {...props}></Icon>
