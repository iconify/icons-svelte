<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7w7r-bld.css';
import '../../css/d/dcs6u0bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7w7r-bld"/><path clip-rule="evenodd" class="dcs6u0bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ssd-round-bold" {...props}></Icon>
