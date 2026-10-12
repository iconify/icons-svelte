<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyo179-vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyo179-vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-x-filled" {...props}></Icon>
