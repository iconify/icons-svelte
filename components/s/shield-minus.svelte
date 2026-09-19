<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqmerm4nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqmerm4nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shield-minus" {...props}></Icon>
