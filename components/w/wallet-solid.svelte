<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd67n86ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd67n86ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wallet-solid" {...props}></Icon>
