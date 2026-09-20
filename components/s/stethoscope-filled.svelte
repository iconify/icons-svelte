<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lterprbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lterprbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stethoscope-filled" {...props}></Icon>
