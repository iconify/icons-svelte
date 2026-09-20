<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks-o0gc_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks-o0gc_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:shopx" {...props}></Icon>
