<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsdd1r8-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsdd1r8-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-left-2-fill" {...props}></Icon>
