<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c2bd161_c.css';
import '../../css/w/w25rgrb9f.css';
import '../../css/i/id02ik75h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="c2bd161_c"/><path class="w25rgrb9f"/><path class="id02ik75h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:whale" {...props}></Icon>
