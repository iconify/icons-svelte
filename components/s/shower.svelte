<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjwn2c9cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjwn2c9cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shower" {...props}></Icon>
