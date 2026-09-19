<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgx6z8bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wgx6z8bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:uzi" {...props}></Icon>
