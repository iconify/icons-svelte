<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cju0fnb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cju0fnb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:scaleway-wordmark" {...props}></Icon>
