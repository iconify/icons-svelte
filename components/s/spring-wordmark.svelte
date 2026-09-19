<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deso3sbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="deso3sbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:spring-wordmark" {...props}></Icon>
