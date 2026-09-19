<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7dgqxs_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7dgqxs_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-outline-alt" {...props}></Icon>
