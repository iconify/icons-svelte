<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2kwq3gxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2kwq3gxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:share-sharp" {...props}></Icon>
