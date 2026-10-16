<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7_v_006l.css';
import '../../css/o/ort-_6bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g7_v_006l"/><path class="ort-_6bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:variable-resistor-20-bold" {...props}></Icon>
