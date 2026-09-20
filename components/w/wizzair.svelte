<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imtb-fd4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imtb-fd4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wizzair" {...props}></Icon>
