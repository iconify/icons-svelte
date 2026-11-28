<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv8qp3i6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv8qp3i6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:speaker-box-solid" {...props}></Icon>
