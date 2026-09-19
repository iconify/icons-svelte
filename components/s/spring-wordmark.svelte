<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj66m2cnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="aj66m2cnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:spring-wordmark" {...props}></Icon>
