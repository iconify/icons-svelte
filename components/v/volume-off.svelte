<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knxbsrbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knxbsrbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:volume-off" {...props}></Icon>
