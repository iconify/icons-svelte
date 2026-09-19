<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2_f_obtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="d2_f_obtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarestop" {...props}></Icon>
