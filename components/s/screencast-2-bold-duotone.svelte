<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baf92pb0v.css';
import '../../css/o/oxe30nuth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="baf92pb0v"/><path class="oxe30nuth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screencast-2-bold-duotone" {...props}></Icon>
