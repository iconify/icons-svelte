<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftgrlccva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftgrlccva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:side-bar-line" {...props}></Icon>
