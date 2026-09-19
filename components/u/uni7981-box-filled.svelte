<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaie1r4rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kaie1r4rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni7981-box-filled" {...props}></Icon>
