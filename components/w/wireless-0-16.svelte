<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyjr-7brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pyjr-7brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wireless-0-16" {...props}></Icon>
