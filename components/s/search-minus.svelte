<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e41hi2rog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e41hi2rog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:search-minus" {...props}></Icon>
