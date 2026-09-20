<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfe2xo-6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mfe2xo-6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wrap-arch-solid" {...props}></Icon>
