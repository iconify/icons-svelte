<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in52ayi5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in52ayi5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-odin-project" {...props}></Icon>
