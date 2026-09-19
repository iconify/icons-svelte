<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5wgs_bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u5wgs_bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spider-alt" {...props}></Icon>
