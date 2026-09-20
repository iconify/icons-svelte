<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpyezrbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kpyezrbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:virtual-reality-solid" {...props}></Icon>
