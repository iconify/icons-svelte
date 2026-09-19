<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icxq6rm-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="icxq6rm-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:smitten" {...props}></Icon>
