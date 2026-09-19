<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvm3z5b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvm3z5b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tree-02" {...props}></Icon>
