<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0fw8pbdn.css';
import '../../css/r/rkj0d4ldk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0fw8pbdn"/><path class="rkj0d4ldk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:save" {...props}></Icon>
