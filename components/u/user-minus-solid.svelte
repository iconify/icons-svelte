<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub4w97u6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ub4w97u6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:user-minus-solid" {...props}></Icon>
