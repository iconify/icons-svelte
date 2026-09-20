<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exm41o2bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="exm41o2bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:rss" {...props}></Icon>
