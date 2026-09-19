<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff_jb8byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ff_jb8byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vlang" {...props}></Icon>
