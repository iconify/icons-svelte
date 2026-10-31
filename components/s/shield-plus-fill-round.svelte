<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxj0mf-xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxj0mf-xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-plus-fill-round" {...props}></Icon>
