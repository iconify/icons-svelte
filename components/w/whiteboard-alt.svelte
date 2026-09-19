<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deb4nz_eq.css';
import '../../css/f/fea8sczxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b deb4nz_eq"/><path class="b fea8sczxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:whiteboard-alt" {...props}></Icon>
