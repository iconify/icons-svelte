<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjk79fo0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjk79fo0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:row-horizontal" {...props}></Icon>
