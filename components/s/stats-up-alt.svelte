<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpv6dt-5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpv6dt-5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:stats-up-alt" {...props}></Icon>
