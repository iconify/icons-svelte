<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx9xdw4tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx9xdw4tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-cells-large" {...props}></Icon>
