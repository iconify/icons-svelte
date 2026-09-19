<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy64nx-nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sy64nx-nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:spyder-wordmark" {...props}></Icon>
