<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iec_14b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iec_14b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:webcam" {...props}></Icon>
