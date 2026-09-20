<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trh51ymmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trh51ymmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-check-filled" {...props}></Icon>
