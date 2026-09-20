<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiau1be2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiau1be2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:unicycle" {...props}></Icon>
