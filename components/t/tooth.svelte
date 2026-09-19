<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_g8uo67w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h_g8uo67w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tooth" {...props}></Icon>
