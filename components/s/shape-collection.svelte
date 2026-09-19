<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/s/sq7x27b-s.css';
import '../../css/y/yphewc7qd.css';
import '../../css/o/orp2owizz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sq7x27b-s"/><circle class="yphewc7qd"/><path class="orp2owizz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shape-collection" {...props}></Icon>
