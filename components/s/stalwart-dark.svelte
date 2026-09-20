<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq4fvhb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bq4fvhb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stalwart-dark" {...props}></Icon>
