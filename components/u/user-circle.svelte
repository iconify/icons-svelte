<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2kvjdb3j.css';
import '../../css/a/a0a-tm2rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2kvjdb3j"/><path class="a0a-tm2rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:user-circle" {...props}></Icon>
