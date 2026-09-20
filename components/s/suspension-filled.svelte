<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4l6txb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4l6txb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:suspension-filled" {...props}></Icon>
