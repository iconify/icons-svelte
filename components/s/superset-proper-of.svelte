<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3ay59fmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3ay59fmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:superset-proper-of" {...props}></Icon>
