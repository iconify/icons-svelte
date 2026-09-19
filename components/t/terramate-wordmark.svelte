<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8ebn724t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b8ebn724t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:terramate-wordmark" {...props}></Icon>
