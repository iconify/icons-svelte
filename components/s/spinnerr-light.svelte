<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u63q-cboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u63q-cboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spinnerr-light" {...props}></Icon>
