<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqjy40bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zqjy40bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:team-idea" {...props}></Icon>
