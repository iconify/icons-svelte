<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrgf_rbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zrgf_rbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:universal-access-alt" {...props}></Icon>
