<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcl2urh4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcl2urh4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:testrail" {...props}></Icon>
