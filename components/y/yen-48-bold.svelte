<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp8l54blm.css';
import '../../css/u/udr_1ybfu.css';
import '../../css/y/ymqwf0tfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bp8l54blm"/><path class="udr_1ybfu"/><path class="ymqwf0tfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:yen-48-bold" {...props}></Icon>
