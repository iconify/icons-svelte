<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzvj8vt_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzvj8vt_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unhappy-dizzy-fill" {...props}></Icon>
