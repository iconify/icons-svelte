<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzac1ibbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzac1ibbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:zap" {...props}></Icon>
