<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/x/x3ffeyb2c.css';
import '../../css/q/q33bbjb-k.css';
import '../../css/e/e05kljyix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x3ffeyb2c"/><path class="q33bbjb-k"/><path class="e05kljyix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:truck-monster" {...props}></Icon>
