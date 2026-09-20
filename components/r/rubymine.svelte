<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmekz27sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmekz27sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rubymine" {...props}></Icon>
