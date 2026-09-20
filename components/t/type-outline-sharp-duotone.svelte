<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsf_qtbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsf_qtbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:type-outline-sharp-duotone" {...props}></Icon>
