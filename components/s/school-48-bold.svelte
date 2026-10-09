<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr5mir7zh.css';
import '../../css/c/ce8x0bd0z.css';
import '../../css/q/qb8zetrno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kr5mir7zh"/><path class="ce8x0bd0z"/><path class="qb8zetrno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:school-48-bold" {...props}></Icon>
