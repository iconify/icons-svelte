<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr32dwnzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nr32dwnzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-up-outline" {...props}></Icon>
