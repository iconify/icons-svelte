<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gquzl-boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gquzl-boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:twitter" {...props}></Icon>
