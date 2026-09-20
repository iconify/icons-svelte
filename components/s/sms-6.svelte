<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhehwf5ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhehwf5ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sms-6" {...props}></Icon>
