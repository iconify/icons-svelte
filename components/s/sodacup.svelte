<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjkki5lld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="gjkki5lld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sodacup" {...props}></Icon>
