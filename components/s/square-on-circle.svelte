<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djer2lbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="djer2lbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-on-circle" {...props}></Icon>
