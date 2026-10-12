<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys0mczbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys0mczbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:table-cells-merge-filled" {...props}></Icon>
