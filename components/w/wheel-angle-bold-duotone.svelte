<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se4__r1yu.css';
import '../../css/j/jbg5enbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="se4__r1yu"/><path class="jbg5enbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wheel-angle-bold-duotone" {...props}></Icon>
