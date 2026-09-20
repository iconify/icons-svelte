<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8i36fqgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8i36fqgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stumble-upon-2ing-logo-block" {...props}></Icon>
