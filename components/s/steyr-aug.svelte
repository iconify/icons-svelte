<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhxbf2bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jhxbf2bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:steyr-aug" {...props}></Icon>
