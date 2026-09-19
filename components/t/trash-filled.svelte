<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwh7i9_ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwh7i9_ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:trash-filled" {...props}></Icon>
