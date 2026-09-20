<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfmsc6ufm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qfmsc6ufm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:treasure-chest-solid" {...props}></Icon>
