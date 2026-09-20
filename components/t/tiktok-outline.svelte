<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/assbk1zjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="assbk1zjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tiktok-outline" {...props}></Icon>
