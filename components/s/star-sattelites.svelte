<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw0hcjblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jw0hcjblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-sattelites" {...props}></Icon>
