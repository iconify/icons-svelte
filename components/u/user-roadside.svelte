<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mn_gx6bsn.css';
import '../../css/s/shsaom4fn.css';
import '../../css/a/ak3jr5b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mn_gx6bsn"/><path class="shsaom4fn"/><path class="ak3jr5b-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-roadside" {...props}></Icon>
