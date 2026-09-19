<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am3kbiccg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="am3kbiccg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:umbrella" {...props}></Icon>
