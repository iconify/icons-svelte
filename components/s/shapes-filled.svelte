<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4a8t74cl.css';
import '../../css/g/g-6i4by5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4a8t74cl"/><rect class="g-6i4by5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shapes-filled" {...props}></Icon>
