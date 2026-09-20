<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq_-3f6bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq_-3f6bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:timer-alt-filled" {...props}></Icon>
