<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w35xc6b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="w35xc6b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:star-fat" {...props}></Icon>
