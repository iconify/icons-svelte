<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mprhoobup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":14};
const content = `<path class="mprhoobup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:youtube" {...props}></Icon>
