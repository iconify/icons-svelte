<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8s4vkb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o8s4vkb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:sketch-logo-solid" {...props}></Icon>
