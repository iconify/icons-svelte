<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n44pvu52s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n44pvu52s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:users3-filled" {...props}></Icon>
