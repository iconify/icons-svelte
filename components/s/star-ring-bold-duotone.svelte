<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj9upir-e.css';
import '../../css/y/yjxhxvben.css';
import '../../css/y/yz0ivnopn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj9upir-e"/><path class="yjxhxvben"/><path clip-rule="evenodd" class="yz0ivnopn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-ring-bold-duotone" {...props}></Icon>
