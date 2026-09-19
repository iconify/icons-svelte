<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joqy0-_5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="joqy0-_5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:toolbox" {...props}></Icon>
