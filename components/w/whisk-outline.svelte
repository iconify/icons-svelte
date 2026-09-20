<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6ow-cbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6ow-cbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:whisk-outline" {...props}></Icon>
