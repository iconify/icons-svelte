<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypn47kb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypn47kb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:save" {...props}></Icon>
