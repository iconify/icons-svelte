<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-pephb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t-pephb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:woman" {...props}></Icon>
