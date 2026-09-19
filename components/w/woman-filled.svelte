<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2u2bwrjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2u2bwrjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:woman-filled" {...props}></Icon>
