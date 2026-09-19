<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y97vgsb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y97vgsb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:underground-cave" {...props}></Icon>
