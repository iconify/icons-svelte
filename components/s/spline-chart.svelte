<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvd31abxp.css';
import '../../css/u/uyos10o5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nvd31abxp"/><path class="uyos10o5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:spline-chart" {...props}></Icon>
