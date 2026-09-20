<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttuin7bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ttuin7bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:triangle-flag" {...props}></Icon>
