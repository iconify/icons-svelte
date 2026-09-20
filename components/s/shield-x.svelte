<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucil41bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucil41bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-x" {...props}></Icon>
