<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilzi5vbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilzi5vbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:striking-balls" {...props}></Icon>
