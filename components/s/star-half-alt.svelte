<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rluezkbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rluezkbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:star-half-alt" {...props}></Icon>
