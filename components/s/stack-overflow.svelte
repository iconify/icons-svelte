<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajvt07bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ajvt07bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:stack-overflow" {...props}></Icon>
