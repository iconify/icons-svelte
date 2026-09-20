<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh9e62b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh9e62b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:shutter-alt" {...props}></Icon>
