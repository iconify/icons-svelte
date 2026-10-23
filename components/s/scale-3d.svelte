<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7orblb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7orblb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scale-3d" {...props}></Icon>
