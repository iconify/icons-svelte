<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azpodsbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azpodsbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:shield" {...props}></Icon>
