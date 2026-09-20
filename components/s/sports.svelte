<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j753kt9-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="j753kt9-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:sports" {...props}></Icon>
