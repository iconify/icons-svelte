<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzpjlsbtf.css';
import '../../css/s/siuoblqsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yzpjlsbtf"/><path class="siuoblqsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-20-bold" {...props}></Icon>
