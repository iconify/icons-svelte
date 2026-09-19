<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssb7-fbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1024};
const content = `<path class="ssb7-fbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tank" {...props}></Icon>
