<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pytm-kb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pytm-kb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:square-enix-logo-block" {...props}></Icon>
