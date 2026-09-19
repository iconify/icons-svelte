<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6memojec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z6memojec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-03-the-empress" {...props}></Icon>
