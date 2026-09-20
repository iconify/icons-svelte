<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1h8neb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1h8neb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wind-turbine-sharp" {...props}></Icon>
