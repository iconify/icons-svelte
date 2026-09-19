<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkq06-bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nkq06-bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:test-auto-solid" {...props}></Icon>
