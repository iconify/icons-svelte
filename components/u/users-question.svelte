<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-eh1fc1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-eh1fc1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users-question" {...props}></Icon>
