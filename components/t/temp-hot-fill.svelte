<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b497d-byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b497d-byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:temp-hot-fill" {...props}></Icon>
