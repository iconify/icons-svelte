<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b833w1u7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b833w1u7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:twinkly" {...props}></Icon>
