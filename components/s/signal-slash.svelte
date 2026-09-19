<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xox_g4bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xox_g4bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:signal-slash" {...props}></Icon>
