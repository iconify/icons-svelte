<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l532xub4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l532xub4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:straighten" {...props}></Icon>
