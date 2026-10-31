<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppmq00bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ppmq00bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-padding-left-filled" {...props}></Icon>
