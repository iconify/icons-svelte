<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd9-tny0x.css';
import '../../css/n/ndt9adc_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cd9-tny0x"/><path class="ndt9adc_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sqlalchemy-wordmark" {...props}></Icon>
