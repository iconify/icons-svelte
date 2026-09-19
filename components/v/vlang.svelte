<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5o67xb4n.css';
import '../../css/v/vclaoe-gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v5o67xb4n"/><path class="vclaoe-gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vlang" {...props}></Icon>
