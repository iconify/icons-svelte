<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbp5g-0ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbp5g-0ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:store-clock" {...props}></Icon>
