<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb-zycb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hb-zycb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:scissors" {...props}></Icon>
