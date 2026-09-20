<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0vr8_z-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0vr8_z-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ticket3-filled" {...props}></Icon>
