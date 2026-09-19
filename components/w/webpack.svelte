<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et-6srbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="et-6srbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:webpack" {...props}></Icon>
