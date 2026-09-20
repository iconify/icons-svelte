<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtuoe68jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtuoe68jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:smartphone-line" {...props}></Icon>
