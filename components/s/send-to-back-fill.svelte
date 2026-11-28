<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaq1hab2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vaq1hab2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:send-to-back-fill" {...props}></Icon>
