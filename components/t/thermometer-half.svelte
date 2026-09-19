<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsv_bw40g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qsv_bw40g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:thermometer-half" {...props}></Icon>
