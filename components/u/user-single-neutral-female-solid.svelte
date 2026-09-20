<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5_cdvbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5_cdvbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-single-neutral-female-solid" {...props}></Icon>
