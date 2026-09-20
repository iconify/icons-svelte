<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nws0tzb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nws0tzb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tape-cassette-record-solid" {...props}></Icon>
