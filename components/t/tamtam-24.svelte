<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp-rp12lq.css';
import '../../css/r/rx12m6nmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp-rp12lq"/><path clip-rule="evenodd" class="rx12m6nmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:tamtam-24" {...props}></Icon>
