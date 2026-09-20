<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh_79lu8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh_79lu8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sad-cry" {...props}></Icon>
