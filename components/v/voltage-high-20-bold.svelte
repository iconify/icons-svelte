<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2eib-bha.css';
import '../../css/g/gsrfvdbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o2eib-bha"/><path class="gsrfvdbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-high-20-bold" {...props}></Icon>
