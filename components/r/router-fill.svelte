<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cau7m0b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cau7m0b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:router-fill" {...props}></Icon>
