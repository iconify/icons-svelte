<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_57g8b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_57g8b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:six-solid" {...props}></Icon>
