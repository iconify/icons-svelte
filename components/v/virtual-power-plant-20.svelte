<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbv3grl-l.css';
import '../../css/i/idfrb-b4g.css';
import '../../css/k/kiditcb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jbv3grl-l"/><path class="idfrb-b4g"/><path class="kiditcb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:virtual-power-plant-20" {...props}></Icon>
