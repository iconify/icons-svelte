<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi49o-bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi49o-bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tallymark-2" {...props}></Icon>
