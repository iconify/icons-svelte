<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt7mp2tnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kt7mp2tnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:styledcomponents" {...props}></Icon>
