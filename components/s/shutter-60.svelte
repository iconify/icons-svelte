<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxw8ynnbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxw8ynnbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shutter-60" {...props}></Icon>
