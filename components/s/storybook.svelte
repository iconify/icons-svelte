<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i08er2b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="i08er2b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:storybook" {...props}></Icon>
