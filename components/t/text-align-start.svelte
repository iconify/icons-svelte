<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm9pbsgds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm9pbsgds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:text-align-start" {...props}></Icon>
