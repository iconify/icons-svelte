<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puo-53u7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="puo-53u7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:web2py" {...props}></Icon>
