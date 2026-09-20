<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkcc6b92k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tkcc6b92k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shirt-solid" {...props}></Icon>
