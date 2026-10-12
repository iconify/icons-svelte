<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slb2x7b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slb2x7b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:skip-forward-filled" {...props}></Icon>
