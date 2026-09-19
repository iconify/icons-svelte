<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9eyilbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="t9eyilbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:skype" {...props}></Icon>
