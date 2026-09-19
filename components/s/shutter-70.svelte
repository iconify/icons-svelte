<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drlc3ff8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drlc3ff8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shutter-70" {...props}></Icon>
