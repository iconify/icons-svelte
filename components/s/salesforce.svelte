<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap81if3yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ap81if3yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:salesforce" {...props}></Icon>
