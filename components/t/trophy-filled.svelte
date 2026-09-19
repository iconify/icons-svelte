<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnfsmhb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnfsmhb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:trophy-filled" {...props}></Icon>
