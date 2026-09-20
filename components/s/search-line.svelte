<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep-je_kdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep-je_kdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-line" {...props}></Icon>
