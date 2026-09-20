<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc7cgqb6v.css';
import '../../css/r/r24iznqrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc7cgqb6v"/><path class="r24iznqrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:send-email-fly" {...props}></Icon>
