<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4tokcr5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k4tokcr5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sun-fill-20" {...props}></Icon>
