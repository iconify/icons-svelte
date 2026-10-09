<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz-knsbvd.css';
import '../../css/u/umxpd67pc.css';
import '../../css/u/usgxssb2k.css';
import '../../css/r/rnrvi0mga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vz-knsbvd"/><path class="umxpd67pc"/><path class="usgxssb2k"/><path class="rnrvi0mga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-snowflake-48-bold" {...props}></Icon>
