<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsw7fgbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsw7fgbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:theaters-filled" {...props}></Icon>
