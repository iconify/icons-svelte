<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx3xu4_0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yx3xu4_0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-bug2" {...props}></Icon>
