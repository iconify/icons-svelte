<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyzjse4-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyzjse4-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:skip-next" {...props}></Icon>
