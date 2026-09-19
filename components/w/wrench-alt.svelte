<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwg2n69-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jwg2n69-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:wrench-alt" {...props}></Icon>
