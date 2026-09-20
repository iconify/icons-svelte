<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gawxdebah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gawxdebah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tab-filled" {...props}></Icon>
