<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy2qybcvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy2qybcvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:stagel-light-2" {...props}></Icon>
