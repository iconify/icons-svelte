<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9wmffbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z9wmffbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ruble-sign" {...props}></Icon>
