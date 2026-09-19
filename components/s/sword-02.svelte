<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/ljkplmvoy.css';
import '../../css/w/w9_ugvb0e.css';
import '../../css/h/hfutfmpoa.css';
import '../../css/i/i9gyr2bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ljkplmvoy"/><path class="w9_ugvb0e"/><path class="hfutfmpoa"/><path class="i9gyr2bxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sword-02" {...props}></Icon>
