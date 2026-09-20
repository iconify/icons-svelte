<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em4_z4t5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="em4_z4t5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:wrench-flat" {...props}></Icon>
