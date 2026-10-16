<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8dezzb1i.css';
import '../../css/x/x5bj1qhem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s8dezzb1i"/><path class="x5bj1qhem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:winch-20" {...props}></Icon>
