<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv1k6e41z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wv1k6e41z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:target" {...props}></Icon>
