<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvjav9xzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvjav9xzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:savg" {...props}></Icon>
