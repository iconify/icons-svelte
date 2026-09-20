<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tffhiiorp.css';
import '../../css/z/z9jk2sgfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tffhiiorp"/><path class="z9jk2sgfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trend-arrow-down-duotone" {...props}></Icon>
