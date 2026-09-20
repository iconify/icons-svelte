<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiyq-lezc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="uiyq-lezc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:sledding" {...props}></Icon>
