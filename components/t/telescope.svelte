<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw8j8bb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw8j8bb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:telescope" {...props}></Icon>
