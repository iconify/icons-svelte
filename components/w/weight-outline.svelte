<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz5jy1b0j.css';
import '../../css/p/pcxysz9ao.css';
import '../../css/v/vwld5md-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gz5jy1b0j"/><path class="pcxysz9ao"/><path clip-rule="evenodd" class="vwld5md-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:weight-outline" {...props}></Icon>
