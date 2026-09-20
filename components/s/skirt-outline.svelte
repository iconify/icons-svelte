<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiy3i7hdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oiy3i7hdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skirt-outline" {...props}></Icon>
