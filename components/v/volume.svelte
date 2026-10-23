<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlei7i_rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlei7i_rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:volume" {...props}></Icon>
