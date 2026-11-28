<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhjwhkm5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhjwhkm5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sink-solid" {...props}></Icon>
