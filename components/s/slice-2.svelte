<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfortsbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="gfortsbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:slice-2" {...props}></Icon>
