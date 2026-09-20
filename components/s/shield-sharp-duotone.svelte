<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0du8hobj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0du8hobj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shield-sharp-duotone" {...props}></Icon>
