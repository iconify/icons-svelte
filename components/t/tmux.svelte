<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyoyq5boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyoyq5boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tmux" {...props}></Icon>
