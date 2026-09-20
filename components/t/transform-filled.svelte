<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9n0dy_jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9n0dy_jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:transform-filled" {...props}></Icon>
