<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kf_jk0b5q.css';
import '../../css/q/q44msqbev.css';
import '../../css/c/co51_lt9h.css';
import '../../css/r/rvb9hdc8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="kf_jk0b5q"/><path clip-rule="evenodd" class="q44msqbev"/><path class="co51_lt9h"/><path clip-rule="evenodd" class="rvb9hdc8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:temperature-hot-outline" {...props}></Icon>
