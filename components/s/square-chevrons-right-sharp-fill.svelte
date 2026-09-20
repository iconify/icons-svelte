<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_o34ob-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_o34ob-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevrons-right-sharp-fill" {...props}></Icon>
