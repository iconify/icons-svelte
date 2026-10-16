<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujn-tbcgw.css';
import '../../css/r/r7__an0bz.css';
import '../../css/g/gcjjvpb6i.css';
import '../../css/a/as8ixpmmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ujn-tbcgw"/><path class="r7__an0bz"/><path class="gcjjvpb6i"/><path class="as8ixpmmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:telemetry-20-bold" {...props}></Icon>
