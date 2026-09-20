<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6_m11bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6_m11bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-position-bottom" {...props}></Icon>
