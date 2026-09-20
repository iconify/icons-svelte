<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lio503b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lio503b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:whisks" {...props}></Icon>
