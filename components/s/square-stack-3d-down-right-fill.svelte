<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in_3xv-0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="in_3xv-0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-stack-3d-down-right-fill" {...props}></Icon>
