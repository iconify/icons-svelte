<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugki3qq4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ugki3qq4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:stackexchange" {...props}></Icon>
