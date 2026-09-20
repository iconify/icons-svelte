<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz_11uu-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_11uu-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tunein" {...props}></Icon>
