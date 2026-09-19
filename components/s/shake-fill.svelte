<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl1h56gff.css';
import '../../css/z/zoh-vz08z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl1h56gff"/><path class="zoh-vz08z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:shake-fill" {...props}></Icon>
