<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8na0-o0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b8na0-o0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:save-as" {...props}></Icon>
