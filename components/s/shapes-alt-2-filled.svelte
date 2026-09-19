<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttk8q5brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttk8q5brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shapes-alt-2-filled" {...props}></Icon>
