<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuaqh7tpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuaqh7tpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:table-plus-line" {...props}></Icon>
