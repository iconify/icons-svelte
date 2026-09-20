<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9xo4xb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9xo4xb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:tablet" {...props}></Icon>
