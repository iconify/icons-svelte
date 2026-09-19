<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw9xuwfok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dw9xuwfok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:umbrella-fill" {...props}></Icon>
