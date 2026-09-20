<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jki42v96b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jki42v96b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:send" {...props}></Icon>
