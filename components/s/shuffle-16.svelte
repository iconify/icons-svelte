<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mou012obv.css';
import '../../css/o/ozw-6jbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mou012obv"/><path class="ozw-6jbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:shuffle-16" {...props}></Icon>
