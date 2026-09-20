<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssc-nkb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssc-nkb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:text-bar" {...props}></Icon>
