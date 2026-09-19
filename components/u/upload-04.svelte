<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9fx60lvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9fx60lvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:upload-04" {...props}></Icon>
