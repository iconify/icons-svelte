<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8juht2-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8juht2-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:wifi-no" {...props}></Icon>
