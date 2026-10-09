<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6zve7bwi.css';
import '../../css/p/ppk8d-n1m.css';
import '../../css/d/dyrpvlfpb.css';
import '../../css/p/px1s3hbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6zve7bwi"/><path class="ppk8d-n1m"/><path class="dyrpvlfpb"/><path class="px1s3hbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-snowflake-20" {...props}></Icon>
