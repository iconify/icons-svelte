<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swr11abte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swr11abte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:settings2-filled" {...props}></Icon>
