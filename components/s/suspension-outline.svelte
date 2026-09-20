<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp28bbubj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zp28bbubj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suspension-outline" {...props}></Icon>
