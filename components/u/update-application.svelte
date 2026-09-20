<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve2wk1-qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve2wk1-qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:update-application" {...props}></Icon>
