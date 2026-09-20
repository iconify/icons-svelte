<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq_wuqm-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wq_wuqm-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:shop" {...props}></Icon>
