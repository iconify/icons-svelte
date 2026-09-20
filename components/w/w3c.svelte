<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nze6iabmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nze6iabmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:w3c" {...props}></Icon>
