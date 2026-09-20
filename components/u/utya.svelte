<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_dkwcc0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_dkwcc0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:utya" {...props}></Icon>
