<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw4a2-bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw4a2-bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-help-fill-round" {...props}></Icon>
