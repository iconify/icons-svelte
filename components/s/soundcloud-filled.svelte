<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwde-vb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwde-vb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:soundcloud-filled" {...props}></Icon>
