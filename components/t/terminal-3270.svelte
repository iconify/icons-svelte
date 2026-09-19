<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu63veedq.css';
import '../../css/q/qu9ohiqrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nu63veedq"/><path class="qu9ohiqrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:terminal-3270" {...props}></Icon>
