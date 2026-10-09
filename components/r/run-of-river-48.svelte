<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1nb12b5u.css';
import '../../css/e/en62kpb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n1nb12b5u"/><path class="en62kpb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:run-of-river-48" {...props}></Icon>
