<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbm918b9c.css';
import '../../css/n/n7kkcye_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbm918b9c"/><path class="n7kkcye_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:stethoscope" {...props}></Icon>
