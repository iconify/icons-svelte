<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1_fpob7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b1_fpob7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:spicedb" {...props}></Icon>
