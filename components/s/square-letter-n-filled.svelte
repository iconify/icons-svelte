<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry-jzed8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry-jzed8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-n-filled" {...props}></Icon>
