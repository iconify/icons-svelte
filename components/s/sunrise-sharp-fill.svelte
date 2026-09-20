<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uth1sgdmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uth1sgdmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sunrise-sharp-fill" {...props}></Icon>
