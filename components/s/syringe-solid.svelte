<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnhcgbbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dnhcgbbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:syringe-solid" {...props}></Icon>
