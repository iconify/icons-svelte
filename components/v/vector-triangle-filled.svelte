<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx5apzz_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx5apzz_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vector-triangle-filled" {...props}></Icon>
