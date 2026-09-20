<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lczie4blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lczie4blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:swords" {...props}></Icon>
