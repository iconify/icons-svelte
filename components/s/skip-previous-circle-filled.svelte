<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd_e_9btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd_e_9btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:skip-previous-circle-filled" {...props}></Icon>
