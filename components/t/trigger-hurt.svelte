<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix7dw7eey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ix7dw7eey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trigger-hurt" {...props}></Icon>
