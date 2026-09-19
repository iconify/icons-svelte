<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2z7jp5ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2z7jp5ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:unplugged" {...props}></Icon>
