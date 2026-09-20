<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-g6zlbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t-g6zlbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:wasp" {...props}></Icon>
