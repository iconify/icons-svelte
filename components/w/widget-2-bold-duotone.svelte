<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yawhug1ht.css';
import '../../css/i/ikdqng8fd.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/c/czjpdqrfy.css';
import '../../css/m/mz-sgwb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yawhug1ht"/><path class="ikdqng8fd"/><g class="xtpeb-edw"><path class="czjpdqrfy"/><path class="mz-sgwb5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-2-bold-duotone" {...props}></Icon>
