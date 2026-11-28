<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eorq5i2_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eorq5i2_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sushi-heart" {...props}></Icon>
