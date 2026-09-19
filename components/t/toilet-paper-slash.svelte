<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t24_l9b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t24_l9b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:toilet-paper-slash" {...props}></Icon>
