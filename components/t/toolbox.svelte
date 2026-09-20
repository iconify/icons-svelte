<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbs5-sbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbs5-sbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toolbox" {...props}></Icon>
