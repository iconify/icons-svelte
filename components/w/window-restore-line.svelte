<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9ag9pbnz.css';
import '../../css/m/m80teebmh.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 p9ag9pbnz"/><path class="clr-i-outline clr-i-outline-path-2 m80teebmh"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:window-restore-line" {...props}></Icon>
