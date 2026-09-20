<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds3tobcnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds3tobcnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sabanci" {...props}></Icon>
