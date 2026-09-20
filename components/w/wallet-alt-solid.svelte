<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z02-h_bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z02-h_bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wallet-alt-solid" {...props}></Icon>
