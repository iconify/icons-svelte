<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4ap6cvjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n4ap6cvjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:usage-included-use-case" {...props}></Icon>
