<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v50ep0b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v50ep0b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tenzir-wordmark" {...props}></Icon>
