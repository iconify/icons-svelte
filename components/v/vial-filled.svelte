<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2qh-kjya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2qh-kjya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vial-filled" {...props}></Icon>
