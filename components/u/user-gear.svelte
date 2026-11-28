<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s481l7_yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s481l7_yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-gear" {...props}></Icon>
