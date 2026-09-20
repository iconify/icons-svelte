<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru8hiep1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru8hiep1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:xd" {...props}></Icon>
