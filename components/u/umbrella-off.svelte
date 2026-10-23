<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhmlk-_io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhmlk-_io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:umbrella-off" {...props}></Icon>
