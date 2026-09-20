<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk96cpvsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kk96cpvsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yugabytedb" {...props}></Icon>
