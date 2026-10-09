<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejhk40bjj.css';
import '../../css/f/fg50i1ydo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ejhk40bjj"/><path class="fg50i1ydo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vertical-axis-turbine-20-bold" {...props}></Icon>
