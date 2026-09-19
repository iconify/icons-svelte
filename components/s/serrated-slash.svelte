<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_7izibmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_7izibmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:serrated-slash" {...props}></Icon>
