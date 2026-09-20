<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tluiet_ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tluiet_ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:unhappy-filled" {...props}></Icon>
