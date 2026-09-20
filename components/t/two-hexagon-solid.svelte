<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqxoyob7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqxoyob7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:two-hexagon-solid" {...props}></Icon>
