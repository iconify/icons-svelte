<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oosz4acur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oosz4acur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:text-underline-filled" {...props}></Icon>
