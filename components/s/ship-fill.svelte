<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il0bmkb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il0bmkb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ship-fill" {...props}></Icon>
