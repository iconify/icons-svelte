<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac9g9w62l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ac9g9w62l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:scikitlearn" {...props}></Icon>
