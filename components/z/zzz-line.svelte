<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp1_m2brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp1_m2brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:zzz-line" {...props}></Icon>
