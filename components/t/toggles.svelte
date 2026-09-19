<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y75ybwfrp.css';
import '../../css/h/hywly5dak.css';
import '../../css/e/ebmdd0qas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y75ybwfrp"/><path class="hywly5dak"/><path class="ebmdd0qas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toggles" {...props}></Icon>
