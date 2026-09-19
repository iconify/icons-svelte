<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urnq0wzqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="urnq0wzqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:traefikproxy-wordmark" {...props}></Icon>
