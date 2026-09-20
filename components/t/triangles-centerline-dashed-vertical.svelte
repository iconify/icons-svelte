<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkb5lwquw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkb5lwquw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:triangles-centerline-dashed-vertical" {...props}></Icon>
