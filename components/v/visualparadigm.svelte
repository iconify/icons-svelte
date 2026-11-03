<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc2q2zbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nc2q2zbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:visualparadigm" {...props}></Icon>
