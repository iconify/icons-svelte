<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh06ukb7c.css';
import '../../css/c/c3i4qtosu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uh06ukb7c"/><path class="c3i4qtosu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:save-solid" {...props}></Icon>
