<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1gszqbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y1gszqbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:screen-alt-solid" {...props}></Icon>
