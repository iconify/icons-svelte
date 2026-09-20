<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp7g2yimv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp7g2yimv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wind-sharp-two-tone" {...props}></Icon>
