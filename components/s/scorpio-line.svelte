<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkol09bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkol09bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scorpio-line" {...props}></Icon>
