<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3pu76ajn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3pu76ajn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shovel-round" {...props}></Icon>
