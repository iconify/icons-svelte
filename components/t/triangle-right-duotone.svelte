<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmyx8dbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmyx8dbtg primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle-right-duotone" {...props}></Icon>
