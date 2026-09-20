<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il_zhnbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il_zhnbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:upload-1" {...props}></Icon>
