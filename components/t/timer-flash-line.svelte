<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doaasx1ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doaasx1ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:timer-flash-line" {...props}></Icon>
