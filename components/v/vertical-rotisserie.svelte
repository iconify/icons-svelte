<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yog0jzrzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yog0jzrzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vertical-rotisserie" {...props}></Icon>
