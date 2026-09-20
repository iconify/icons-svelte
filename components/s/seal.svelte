<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8clfnmeu.css';
import '../../css/v/vk_1vtl0s.css';
import '../../css/l/lz9v_niow.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/u/uyul9oadq.css';
import '../../css/j/jlo7qacpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="o8clfnmeu"/><path class="vk_1vtl0s"/><path class="lz9v_niow"/><g class="jn8qy4bru"><path class="uyul9oadq"/><path class="jlo7qacpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:seal" {...props}></Icon>
