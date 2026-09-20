<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmrm1ub4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qmrm1ub4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-arrow-curvy-up-down-2-remix" {...props}></Icon>
