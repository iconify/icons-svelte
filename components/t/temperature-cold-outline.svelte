<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xejf2jbsh.css';
import '../../css/w/w7y2rjsln.css';
import '../../css/i/i0sv2zf0k.css';
import '../../css/m/mkbu6bcri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xejf2jbsh"/><path clip-rule="evenodd" class="w7y2rjsln"/><path class="i0sv2zf0k"/><path clip-rule="evenodd" class="mkbu6bcri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:temperature-cold-outline" {...props}></Icon>
