<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n586acbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n586acbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:secret-door" {...props}></Icon>
