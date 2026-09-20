<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nss4h2bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nss4h2bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:scroll" {...props}></Icon>
