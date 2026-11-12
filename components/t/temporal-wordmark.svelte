<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/den0z5b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="den0z5b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:temporal-wordmark" {...props}></Icon>
