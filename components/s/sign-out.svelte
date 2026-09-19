<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1bhs7blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1bhs7blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:sign-out" {...props}></Icon>
