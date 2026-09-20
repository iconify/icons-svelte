<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9as19z5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v9as19z5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shopping-basket-2-solid" {...props}></Icon>
