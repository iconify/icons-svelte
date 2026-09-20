<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnk4x_bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnk4x_bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:wave-right-filled" {...props}></Icon>
