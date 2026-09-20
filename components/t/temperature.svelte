<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp4oqwbqh.css';
import '../../css/i/iynmzp4ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp4oqwbqh"/><circle class="iynmzp4ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:temperature" {...props}></Icon>
