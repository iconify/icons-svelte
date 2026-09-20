<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npy_5y7xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="npy_5y7xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:star-circle-solid" {...props}></Icon>
