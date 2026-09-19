<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mro49xbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mro49xbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:seaborn-wordmark" {...props}></Icon>
