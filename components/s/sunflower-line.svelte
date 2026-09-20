<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxi6jtjqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxi6jtjqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sunflower-line" {...props}></Icon>
