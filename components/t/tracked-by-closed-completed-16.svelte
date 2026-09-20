<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-00eccfu.css';
import '../../css/a/ahjjzsb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w-00eccfu"/><path class="ahjjzsb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tracked-by-closed-completed-16" {...props}></Icon>
