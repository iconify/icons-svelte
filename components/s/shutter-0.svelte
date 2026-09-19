<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg96pwbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg96pwbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shutter-0" {...props}></Icon>
