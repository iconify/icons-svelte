<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9-2lnb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n9-2lnb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:seat" {...props}></Icon>
