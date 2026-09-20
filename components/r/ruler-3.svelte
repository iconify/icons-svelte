<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4ch6u7ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4ch6u7ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ruler-3" {...props}></Icon>
