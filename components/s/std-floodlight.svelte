<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps12n-bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps12n-bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:std-floodlight" {...props}></Icon>
