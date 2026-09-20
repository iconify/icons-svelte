<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on3jn5iqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="on3jn5iqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ssh" {...props}></Icon>
