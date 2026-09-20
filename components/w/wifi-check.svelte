<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b43xt4hkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b43xt4hkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-check" {...props}></Icon>
