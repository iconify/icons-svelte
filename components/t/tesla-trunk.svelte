<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfy829k1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfy829k1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-trunk" {...props}></Icon>
