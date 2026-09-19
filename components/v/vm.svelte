<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-y9v8bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x-y9v8bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:vm" {...props}></Icon>
