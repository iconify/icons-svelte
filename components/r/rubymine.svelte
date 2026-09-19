<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gti5d3bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gti5d3bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rubymine" {...props}></Icon>
