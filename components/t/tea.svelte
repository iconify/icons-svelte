<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu814jo0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xu814jo0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:tea" {...props}></Icon>
