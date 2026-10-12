<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke_8k_97h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke_8k_97h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-to-speech" {...props}></Icon>
