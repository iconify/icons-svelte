<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drare1bjj.css';
import '../../css/z/zyog8pxnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drare1bjj"/><path clip-rule="evenodd" class="zyog8pxnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:telegram" {...props}></Icon>
