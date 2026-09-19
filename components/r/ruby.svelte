<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz2t2e3bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lz2t2e3bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ruby" {...props}></Icon>
