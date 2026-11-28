<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heb4gabhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="heb4gabhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:window-solid" {...props}></Icon>
