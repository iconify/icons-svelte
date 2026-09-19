<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alr3ezbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="alr3ezbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:two-handed-sword" {...props}></Icon>
