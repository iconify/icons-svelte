<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n82y8wbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n82y8wbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:testrail" {...props}></Icon>
