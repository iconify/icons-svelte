<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2r7a0-pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2r7a0-pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zyx" {...props}></Icon>
