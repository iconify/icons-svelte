<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbkmr_byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="rbkmr_byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:viacoin" {...props}></Icon>
