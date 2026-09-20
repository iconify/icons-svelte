<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/x/x6wq2bcno.css';
import '../../css/l/loubjdbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="y9tr6bcfx"><path class="x6wq2bcno"/><path class="loubjdbwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:shazam-logo" {...props}></Icon>
