<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvec1l3uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvec1l3uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:settings-3-line" {...props}></Icon>
