<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfrpoo3dn.css';
import '../../css/t/t_qou-ite.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfrpoo3dn"/><path class="t_qou-ite"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:zoom-out" {...props}></Icon>
