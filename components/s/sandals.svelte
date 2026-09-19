<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs6i5vbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs6i5vbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:sandals" {...props}></Icon>
