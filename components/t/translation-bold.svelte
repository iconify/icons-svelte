<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bfczqwbld.css';
import '../../css/b/bpv8bfbck.css';
import '../../css/s/sgvjp04ko.css';
import '../../css/s/swpqpacuo.css';
import '../../css/r/rwn4wowra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bfczqwbld"/><path class="bpv8bfbck"/><path class="sgvjp04ko"/><path class="swpqpacuo"/><path class="rwn4wowra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:translation-bold" {...props}></Icon>
