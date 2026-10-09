<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2nwdhbfp.css';
import '../../css/o/oke3tmsms.css';
import '../../css/k/kgfy1yblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i2nwdhbfp"/><path class="oke3tmsms"/><path class="kgfy1yblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-street-light-48-bold" {...props}></Icon>
