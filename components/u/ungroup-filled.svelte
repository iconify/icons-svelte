<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk1_f629e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk1_f629e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ungroup-filled" {...props}></Icon>
