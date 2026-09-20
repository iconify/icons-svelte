<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7i7wkb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u7i7wkb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:simit-macro-component-editor" {...props}></Icon>
