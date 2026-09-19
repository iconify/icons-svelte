<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2xa0wbnt.css';
import '../../css/k/k5kt1he2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o2xa0wbnt"/><path class="k5kt1he2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:thunderstorm-sharp" {...props}></Icon>
