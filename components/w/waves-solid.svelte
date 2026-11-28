<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbuo0fbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbuo0fbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:waves-solid" {...props}></Icon>
