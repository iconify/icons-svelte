<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt19m1bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt19m1bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-module" {...props}></Icon>
