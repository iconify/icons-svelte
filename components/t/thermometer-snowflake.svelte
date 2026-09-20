<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t193o3bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t193o3bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:thermometer-snowflake" {...props}></Icon>
