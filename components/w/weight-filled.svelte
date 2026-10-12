<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci2lnnikp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ci2lnnikp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:weight-filled" {...props}></Icon>
