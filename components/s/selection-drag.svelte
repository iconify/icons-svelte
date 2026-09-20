<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whgu202qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whgu202qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selection-drag" {...props}></Icon>
