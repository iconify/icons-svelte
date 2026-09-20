<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eppuz1lar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eppuz1lar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:store-2-solid" {...props}></Icon>
