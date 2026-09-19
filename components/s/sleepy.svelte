<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9irqhbom.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/o/oqwog-bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9irqhbom"/><path class="bwibdw4bb"/><path class="oqwog-bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sleepy" {...props}></Icon>
