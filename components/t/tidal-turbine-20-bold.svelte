<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8n1kw7hi.css';
import '../../css/k/k30a2to6z.css';
import '../../css/d/duoc7ibzo.css';
import '../../css/f/f7ekb8_eq.css';
import '../../css/r/r6mati80e.css';
import '../../css/k/kw5qtrb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e8n1kw7hi"/><path class="k30a2to6z"/><path class="duoc7ibzo"/><path class="f7ekb8_eq"/><path class="r6mati80e"/><path class="kw5qtrb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-turbine-20-bold" {...props}></Icon>
