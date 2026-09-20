<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khm_tcb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khm_tcb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sahibinden" {...props}></Icon>
