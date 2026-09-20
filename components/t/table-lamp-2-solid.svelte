<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqb7_60cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zqb7_60cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:table-lamp-2-solid" {...props}></Icon>
