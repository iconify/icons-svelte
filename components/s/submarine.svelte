<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey3-pfbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":832};
const content = `<path class="ey3-pfbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:submarine" {...props}></Icon>
