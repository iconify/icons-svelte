<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj4dracyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj4dracyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:women-line" {...props}></Icon>
