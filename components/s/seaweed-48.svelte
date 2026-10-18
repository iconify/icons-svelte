<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o60fd0ylo.css';
import '../../css/n/najn_bcni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o60fd0ylo"/><path class="najn_bcni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seaweed-48" {...props}></Icon>
