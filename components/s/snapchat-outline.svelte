<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzve063hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nzve063hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:snapchat-outline" {...props}></Icon>
