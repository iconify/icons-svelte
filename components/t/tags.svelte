<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa1jqjb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-3};
const content = `<path class="sa1jqjb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tags" {...props}></Icon>
