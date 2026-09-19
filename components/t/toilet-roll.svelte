<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdkeixbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdkeixbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toilet-roll" {...props}></Icon>
