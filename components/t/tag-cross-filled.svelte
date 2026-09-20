<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwyfkgblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwyfkgblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tag-cross-filled" {...props}></Icon>
