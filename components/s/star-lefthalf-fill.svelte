<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxhn9i52s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jxhn9i52s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:star-lefthalf-fill" {...props}></Icon>
