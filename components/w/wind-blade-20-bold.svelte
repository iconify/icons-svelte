<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onndsh4cj.css';
import '../../css/d/du94n1byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="onndsh4cj"/><path class="du94n1byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-blade-20-bold" {...props}></Icon>
