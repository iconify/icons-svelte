<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzn16g15g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mzn16g15g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:visualstudio" {...props}></Icon>
