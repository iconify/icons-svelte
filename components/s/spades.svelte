<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms6cqtber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ms6cqtber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spades" {...props}></Icon>
