<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv5_w2gaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv5_w2gaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-minus-corner-round" {...props}></Icon>
