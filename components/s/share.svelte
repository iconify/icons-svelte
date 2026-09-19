<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as1j6b10p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as1j6b10p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:share" {...props}></Icon>
