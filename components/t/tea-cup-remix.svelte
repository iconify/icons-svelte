<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he_9c_4nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="he_9c_4nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:tea-cup-remix" {...props}></Icon>
