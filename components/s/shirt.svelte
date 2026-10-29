<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1_7h9bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1_7h9bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shirt" {...props}></Icon>
