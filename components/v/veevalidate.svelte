<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-jaijzub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w-jaijzub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:veevalidate" {...props}></Icon>
