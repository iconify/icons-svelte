<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tus8v7snr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1408};
const content = `<path class="tus8v7snr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:turkish-lira" {...props}></Icon>
