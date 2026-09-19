<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-34vlb0v.css';
import '../../css/t/t38at1bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-34vlb0v"/><path class="t38at1bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shekel-filled" {...props}></Icon>
