<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oquz9_65a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oquz9_65a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:triangles-centerline-dashed-horizontal-filled" {...props}></Icon>
