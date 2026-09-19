<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otwnocb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="otwnocb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:typo3" {...props}></Icon>
