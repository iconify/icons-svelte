<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqj9z9wrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqj9z9wrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wifi-off" {...props}></Icon>
