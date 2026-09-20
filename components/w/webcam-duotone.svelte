<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yw4ewdbig.css';
import '../../css/r/rgjubxbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="yw4ewdbig"/><path class="rgjubxbat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:webcam-duotone" {...props}></Icon>
