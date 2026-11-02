<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9u4854ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9u4854ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sandstorm-fill" {...props}></Icon>
