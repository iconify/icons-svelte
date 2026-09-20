<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu4p30ims.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lu4p30ims"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:soft-drink-can-solid" {...props}></Icon>
