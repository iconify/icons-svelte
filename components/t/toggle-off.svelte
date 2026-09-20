<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohaewfbtd.css';
import '../../css/v/vx04_ybbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohaewfbtd"/><circle class="vx04_ybbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:toggle-off" {...props}></Icon>
