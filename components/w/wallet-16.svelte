<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoj6c4bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xoj6c4bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wallet-16" {...props}></Icon>
