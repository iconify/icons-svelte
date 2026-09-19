<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjblqxbkz.css';
import '../../css/m/mhg07abei.css';
import '../../css/j/jamog_u4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjblqxbkz"/><path class="mhg07abei"/><path class="jamog_u4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:webhook" {...props}></Icon>
