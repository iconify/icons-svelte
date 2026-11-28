<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms497sa8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ms497sa8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:send-to-back-light" {...props}></Icon>
