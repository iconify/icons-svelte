<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ansc-jpyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ansc-jpyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:traffic-economy-bold" {...props}></Icon>
