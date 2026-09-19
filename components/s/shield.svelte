<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y2ss9hb6d.css';
import '../../css/s/sf0wjubya.css';
import '../../css/s/s4gz9abla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y2ss9hb6d"/><path class="sf0wjubya"/><path class="s4gz9abla"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:shield" {...props}></Icon>
