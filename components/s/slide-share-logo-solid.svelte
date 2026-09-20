<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdat6-bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mdat6-bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:slide-share-logo-solid" {...props}></Icon>
