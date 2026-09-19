<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7euacc-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1472,"height":1792};
const content = `<path class="h7euacc-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:tree" {...props}></Icon>
