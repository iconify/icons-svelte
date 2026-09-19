<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipfks6n4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ipfks6n4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:t-bubble" {...props}></Icon>
