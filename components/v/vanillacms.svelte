<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1bf2ch-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="n1bf2ch-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:vanillacms" {...props}></Icon>
