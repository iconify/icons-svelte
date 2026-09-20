<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc_2yj9om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc_2yj9om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-line-sharp-fill" {...props}></Icon>
