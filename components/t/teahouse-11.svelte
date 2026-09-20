<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf9w5nbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="gf9w5nbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:teahouse-11" {...props}></Icon>
