<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtav2zbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtav2zbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:woocommerce-logo-block" {...props}></Icon>
