<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsf-qnbqy.css';
import '../../css/b/b19x8pyha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsf-qnbqy"/><path class="b19x8pyha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:time-clock-fire-bold" {...props}></Icon>
