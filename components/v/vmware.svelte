<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdhi3-bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdhi3-bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vmware" {...props}></Icon>
