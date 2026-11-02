<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krnl832ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krnl832ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-visible-line" {...props}></Icon>
