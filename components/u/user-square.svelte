<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb0ublros.css';
import '../../css/j/jwnh_illk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb0ublros"/><path class="jwnh_illk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-square" {...props}></Icon>
