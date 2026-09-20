<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7s5e54ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7s5e54ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sbd" {...props}></Icon>
