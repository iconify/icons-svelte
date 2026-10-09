<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl2h9z-2v.css';
import '../../css/o/o_t0ybbes.css';
import '../../css/e/ehtcwob1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bl2h9z-2v"/><path class="o_t0ybbes"/><path class="ehtcwob1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:underground-cable-48" {...props}></Icon>
