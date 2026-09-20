<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdrw_-bzd.css';
import '../../css/m/m0a6ogbci.css';
import '../../css/d/deo436eby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fdrw_-bzd"/><path class="m0a6ogbci"/><path clip-rule="evenodd" class="deo436eby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:task-soon-16" {...props}></Icon>
