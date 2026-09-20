<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8gur4b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8gur4b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:trivago" {...props}></Icon>
