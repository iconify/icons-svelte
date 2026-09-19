<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_fq1yb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_fq1yb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toggle-big-left-filled" {...props}></Icon>
