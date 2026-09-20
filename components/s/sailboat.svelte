<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb9sotsen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb9sotsen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sailboat" {...props}></Icon>
