<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szxpzob-w.css';
import '../../css/n/nhk3unbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="szxpzob-w"/><path class="nhk3unbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:user-man-love" {...props}></Icon>
