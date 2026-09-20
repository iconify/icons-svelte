<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt59dgbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vt59dgbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smile-circle-bold" {...props}></Icon>
