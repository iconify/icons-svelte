<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf57ohj7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tf57ohj7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:video-file" {...props}></Icon>
