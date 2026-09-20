<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1f-wbbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1f-wbbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:trend-micro" {...props}></Icon>
