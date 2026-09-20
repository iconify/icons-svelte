<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3xtuk_0z.css';
import '../../css/x/x6zsqtbjm.css';
import '../../css/p/p8byw9pyu.css';
import '../../css/v/vfms9tbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="x6zsqtbjm"/><path class="p8byw9pyu"/><path class="vfms9tbqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:video-meeting-group" {...props}></Icon>
