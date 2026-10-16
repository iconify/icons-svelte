<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdclrrbld.css';
import '../../css/z/zrqa_4kry.css';
import '../../css/j/j0szhnrrq.css';
import '../../css/d/dlcn8obnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kdclrrbld"/><path class="zrqa_4kry"/><path class="j0szhnrrq"/><path class="dlcn8obnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:soil-carbon-48-bold" {...props}></Icon>
