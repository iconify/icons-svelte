<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f04w38lpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f04w38lpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:traffic-signal" {...props}></Icon>
