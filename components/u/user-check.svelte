<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/i/i48n9wbdl.css';
import '../../css/n/ntqfozbki.css';
import '../../css/l/li06vcqvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="i48n9wbdl"/><path class="ntqfozbki"/><path class="li06vcqvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:user-check" {...props}></Icon>
