<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvj5e0bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvj5e0bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-two" {...props}></Icon>
