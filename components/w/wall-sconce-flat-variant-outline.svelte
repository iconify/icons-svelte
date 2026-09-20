<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw60h-bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw60h-bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wall-sconce-flat-variant-outline" {...props}></Icon>
