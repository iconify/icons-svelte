<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ismtb1bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ismtb1bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:triangle" {...props}></Icon>
