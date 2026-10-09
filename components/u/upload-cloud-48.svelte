<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn0n17h7c.css';
import '../../css/b/b51sehbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fn0n17h7c"/><path class="b51sehbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:upload-cloud-48" {...props}></Icon>
