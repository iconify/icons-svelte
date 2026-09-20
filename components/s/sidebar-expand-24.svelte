<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-q9jk35j.css';
import '../../css/z/z9rr_ubxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-q9jk35j"/><path class="z9rr_ubxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sidebar-expand-24" {...props}></Icon>
