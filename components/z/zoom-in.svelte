<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaxkd8bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uaxkd8bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:zoom-in" {...props}></Icon>
