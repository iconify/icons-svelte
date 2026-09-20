<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx606acgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="sx606acgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:scale-contract" {...props}></Icon>
