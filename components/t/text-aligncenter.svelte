<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta2un9b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ta2un9b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-aligncenter" {...props}></Icon>
