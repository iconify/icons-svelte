<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i57v3jbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i57v3jbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:visual-studio-code" {...props}></Icon>
