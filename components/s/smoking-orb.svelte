<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqv5e8bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dqv5e8bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:smoking-orb" {...props}></Icon>
