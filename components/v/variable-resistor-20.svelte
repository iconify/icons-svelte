<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd76n1f0v.css';
import '../../css/f/flk8b6but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gd76n1f0v"/><path class="flk8b6but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:variable-resistor-20" {...props}></Icon>
