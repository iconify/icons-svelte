<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq9pr2-7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fq9pr2-7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rune-sword" {...props}></Icon>
