<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfra_acnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfra_acnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-woman-book-bold" {...props}></Icon>
