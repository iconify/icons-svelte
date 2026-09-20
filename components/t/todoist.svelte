<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_tld4ojc.css';
import '../../css/b/bu-7bcciv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_tld4ojc"/><path class="bu-7bcciv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:todoist" {...props}></Icon>
