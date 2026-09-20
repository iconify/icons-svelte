<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uwi7ak1nz.css';
import '../../css/h/hjd4hrb9v.css';
import '../../css/l/lf8zclbve.css';
import '../../css/u/unv7mgqkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uwi7ak1nz"/><path class="hjd4hrb9v"/><path class="lf8zclbve"/><path class="unv7mgqkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:video-library" {...props}></Icon>
