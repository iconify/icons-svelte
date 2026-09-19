<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrntv9boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qrntv9boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zip" {...props}></Icon>
