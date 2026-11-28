<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yubwaibfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yubwaibfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:truck-arrow-right" {...props}></Icon>
