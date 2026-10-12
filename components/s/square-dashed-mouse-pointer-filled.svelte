<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwn1u0bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwn1u0bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-dashed-mouse-pointer-filled" {...props}></Icon>
