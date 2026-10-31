<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_atly8co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_atly8co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-terminal-fill-round" {...props}></Icon>
