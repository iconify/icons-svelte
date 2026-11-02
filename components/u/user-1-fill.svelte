<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0mz0abna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0mz0abna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-1-fill" {...props}></Icon>
