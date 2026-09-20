<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzw5gqb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jzw5gqb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:zoom-out-gesture-solid" {...props}></Icon>
