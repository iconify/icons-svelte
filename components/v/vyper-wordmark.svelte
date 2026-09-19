<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu9qb8bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cu9qb8bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vyper-wordmark" {...props}></Icon>
