<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo_u64bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo_u64bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:shuffle" {...props}></Icon>
