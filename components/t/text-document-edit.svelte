<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_k8-vb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w_k8-vb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:text-document-edit" {...props}></Icon>
