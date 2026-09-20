<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq3z-t4xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq3z-t4xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:seek-backward-24" {...props}></Icon>
