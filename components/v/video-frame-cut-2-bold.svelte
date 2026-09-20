<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg6_69hzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zg6_69hzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-frame-cut-2-bold" {...props}></Icon>
