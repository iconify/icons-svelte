<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dktledmnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dktledmnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-smile-line" {...props}></Icon>
