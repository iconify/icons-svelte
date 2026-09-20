<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnyk70yku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lnyk70yku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:route-bold" {...props}></Icon>
