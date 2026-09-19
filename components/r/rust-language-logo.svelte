<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ixacuov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q3ixacuov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rust-language-logo" {...props}></Icon>
