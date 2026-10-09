<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0epiybna.css';
import '../../css/f/f_x7syode.css';
import '../../css/h/hacaudf9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o0epiybna"/><path class="f_x7syode"/><path class="hacaudf9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:virtual-power-plant-20-bold" {...props}></Icon>
