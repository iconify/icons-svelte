<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5hiwnbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5hiwnbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-chevron-double-right-fill-round" {...props}></Icon>
