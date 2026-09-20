<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa5sfhb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fa5sfhb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:route" {...props}></Icon>
