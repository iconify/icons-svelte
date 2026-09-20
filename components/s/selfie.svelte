<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez-7w8b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez-7w8b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:selfie" {...props}></Icon>
