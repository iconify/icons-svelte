<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcb-w99fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tcb-w99fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:tzc" {...props}></Icon>
