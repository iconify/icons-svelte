<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a501rabcl.css';
import '../../css/o/ox7m9zbhk.css';
import '../../css/p/ppn0rybgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a501rabcl"/><path class="ox7m9zbhk"/><path clip-rule="evenodd" class="ppn0rybgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-close-outline" {...props}></Icon>
