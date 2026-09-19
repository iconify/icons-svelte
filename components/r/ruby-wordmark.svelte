<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-1ecmbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b-1ecmbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ruby-wordmark" {...props}></Icon>
