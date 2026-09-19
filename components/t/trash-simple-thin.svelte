<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0v7p9bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0v7p9bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:trash-simple-thin" {...props}></Icon>
