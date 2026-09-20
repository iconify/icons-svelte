<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx6yl2nkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cx6yl2nkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:triangle-flag-solid" {...props}></Icon>
