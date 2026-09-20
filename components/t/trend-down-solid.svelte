<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbtm4g3rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hbtm4g3rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:trend-down-solid" {...props}></Icon>
