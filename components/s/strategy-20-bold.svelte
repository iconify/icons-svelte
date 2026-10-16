<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7qbyuxuw.css';
import '../../css/e/eolgfe9_w.css';
import '../../css/n/nqz5vbbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n7qbyuxuw"/><path class="eolgfe9_w"/><path class="nqz5vbbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:strategy-20-bold" {...props}></Icon>
