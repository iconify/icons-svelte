<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0vw-qqqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0vw-qqqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-image-solid" {...props}></Icon>
