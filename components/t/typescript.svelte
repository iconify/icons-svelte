<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrmk3r6sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yrmk3r6sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:typescript" {...props}></Icon>
