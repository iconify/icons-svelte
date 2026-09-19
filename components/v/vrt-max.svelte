<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8o724obr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8o724obr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:vrt-max" {...props}></Icon>
