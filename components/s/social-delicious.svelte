<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vohgu1asq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vohgu1asq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-delicious" {...props}></Icon>
