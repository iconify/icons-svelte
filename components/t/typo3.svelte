<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czjjpdb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="czjjpdb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:typo3" {...props}></Icon>
