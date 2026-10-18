<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rplblqbon.css';
import '../../css/n/nlh68myqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rplblqbon"/><path class="nlh68myqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:state-of-charge-48" {...props}></Icon>
