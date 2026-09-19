<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5a9ri5nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5a9ri5nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shiny-apple" {...props}></Icon>
