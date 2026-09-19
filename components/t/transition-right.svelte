<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tg7r5obnp.css';
import '../../css/a/ar0z5_bbv.css';
import '../../css/a/aotcudf0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tg7r5obnp"/><path class="ar0z5_bbv"/><path class="aotcudf0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:transition-right" {...props}></Icon>
