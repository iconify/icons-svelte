<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8hfccbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":85,"height":26};
const content = `<path class="p8hfccbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-connect-26" {...props}></Icon>
