<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fln_4q79i.css';
import '../../css/m/m3_jbieof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fln_4q79i"/><path class="m3_jbieof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sure-finance" {...props}></Icon>
