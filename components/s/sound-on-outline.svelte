<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq_e61vnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tq_e61vnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sound-on-outline" {...props}></Icon>
