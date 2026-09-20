<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr6nkx0mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr6nkx0mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shape" {...props}></Icon>
