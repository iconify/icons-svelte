<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8twbp5bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u8twbp5bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:seaplane-takeoff" {...props}></Icon>
