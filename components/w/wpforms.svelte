<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hixwd4_oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="hixwd4_oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:wpforms" {...props}></Icon>
