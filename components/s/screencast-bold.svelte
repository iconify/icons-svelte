<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcm12ccjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcm12ccjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screencast-bold" {...props}></Icon>
