<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr8j-xj6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hr8j-xj6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:turbo" {...props}></Icon>
