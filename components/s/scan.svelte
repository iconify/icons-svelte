<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcw_0vb3n.css';
import '../../css/r/ro-apk0gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xcw_0vb3n"/><path class="ro-apk0gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scan" {...props}></Icon>
