<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6e4nk4sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6e4nk4sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:syringe" {...props}></Icon>
