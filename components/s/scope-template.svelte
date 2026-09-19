<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwe_44r1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qwe_44r1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:scope-template" {...props}></Icon>
