<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m49a0tnlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m49a0tnlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:squircle-dashed" {...props}></Icon>
