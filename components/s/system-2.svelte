<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxu1l1pmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxu1l1pmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-2" {...props}></Icon>
