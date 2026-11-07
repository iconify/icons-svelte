<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6d250bwp.css';
import '../../css/r/rr_nhybqq.css';
import '../../css/j/jt-vrxbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6d250bwp"/><path class="rr_nhybqq"/><path clip-rule="evenodd" class="jt-vrxbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-minus-rounded-outline" {...props}></Icon>
