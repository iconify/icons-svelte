<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5g-q6bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5g-q6bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-fill-round" {...props}></Icon>
