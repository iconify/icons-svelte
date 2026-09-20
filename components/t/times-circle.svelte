<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0_sj-vvr.css';
import '../../css/m/maum05bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0_sj-vvr"/><path class="maum05bfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:times-circle" {...props}></Icon>
