<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpzk_4i8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gpzk_4i8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:spray" {...props}></Icon>
