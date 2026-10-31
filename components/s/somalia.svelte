<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiewx4bml.css';
import '../../css/t/ta73ae7hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="xiewx4bml"/><path class="ta73ae7hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:somalia" {...props}></Icon>
