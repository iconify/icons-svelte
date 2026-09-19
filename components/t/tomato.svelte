<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mk1u0xbci.css';
import '../../css/t/tlff4acvo.css';
import '../../css/h/h330vwkrl.css';
import '../../css/n/ns5-vub8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="mk1u0xbci"/><path class="tlff4acvo"/><path class="h330vwkrl"/><path class="ns5-vub8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:tomato" {...props}></Icon>
