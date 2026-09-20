<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k54_jgbmz.css';
import '../../css/w/wwzneb9rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k54_jgbmz"/><path class="wwzneb9rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:usergroup-add-filled" {...props}></Icon>
