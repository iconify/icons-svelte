<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe6u85bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qe6u85bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:triangle" {...props}></Icon>
