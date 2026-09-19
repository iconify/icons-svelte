<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwwb-nbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xwwb-nbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:stethoscope-outline-24px" {...props}></Icon>
