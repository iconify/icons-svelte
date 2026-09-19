<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnq-f2bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qnq-f2bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tigerbeetle-wordmark" {...props}></Icon>
