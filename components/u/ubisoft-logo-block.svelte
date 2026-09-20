<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du_ov4bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="du_ov4bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ubisoft-logo-block" {...props}></Icon>
