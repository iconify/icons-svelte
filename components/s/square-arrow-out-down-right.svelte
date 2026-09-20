<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfdzzmezu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfdzzmezu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-arrow-out-down-right" {...props}></Icon>
