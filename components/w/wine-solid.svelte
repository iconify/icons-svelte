<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgy--9bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgy--9bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:wine-solid" {...props}></Icon>
