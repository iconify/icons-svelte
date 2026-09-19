<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_-8nybyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_-8nybyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shrink-left-filled" {...props}></Icon>
