<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf027v8gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zf027v8gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yugabytedb-dark" {...props}></Icon>
