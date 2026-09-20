<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c64022b1f.css';
import '../../css/g/g2rcx6i-o.css';
import '../../css/i/i5vl1gfpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c64022b1f"/><rect class="g2rcx6i-o"/><path class="i5vl1gfpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:vector-square-alt" {...props}></Icon>
