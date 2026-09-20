<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow2q_cqck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow2q_cqck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sign-right" {...props}></Icon>
