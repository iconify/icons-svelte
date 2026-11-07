<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yx7codbhz.css';
import '../../css/y/yn2dbebtk.css';
import '../../css/e/e-mft8bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yx7codbhz"/><path class="yn2dbebtk"/><path class="e-mft8bme"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:snowflake-broken" {...props}></Icon>
