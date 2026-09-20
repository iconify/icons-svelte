<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1fvhep4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l1fvhep4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:truck" {...props}></Icon>
