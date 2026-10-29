<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkbledcac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkbledcac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sticky-note-solid" {...props}></Icon>
