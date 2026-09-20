<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5dwkmnlz.css';
import '../../css/w/w50wxabok.css';
import '../../css/g/gdzqqzccu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1104,"height":1104};
const content = `<path class="f5dwkmnlz"/><path class="w50wxabok"/><path class="gdzqqzccu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:visernic" {...props}></Icon>
