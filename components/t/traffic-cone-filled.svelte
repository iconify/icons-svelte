<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqeh_xbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqeh_xbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:traffic-cone-filled" {...props}></Icon>
