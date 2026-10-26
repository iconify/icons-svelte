<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wze0azn8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wze0azn8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:sanity" {...props}></Icon>
