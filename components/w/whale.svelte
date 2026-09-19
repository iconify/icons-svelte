<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a4i6dabiz.css';
import '../../css/i/itsk313tz.css';
import '../../css/h/he1sk-rbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="a4i6dabiz"/><path class="itsk313tz"/><circle class="he1sk-rbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:whale" {...props}></Icon>
