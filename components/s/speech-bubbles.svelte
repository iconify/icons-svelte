<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utxo58v5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="utxo58v5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:speech-bubbles" {...props}></Icon>
