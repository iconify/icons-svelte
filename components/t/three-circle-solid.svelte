<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovf2g8dss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovf2g8dss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:three-circle-solid" {...props}></Icon>
