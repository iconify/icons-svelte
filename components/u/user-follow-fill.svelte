<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d87_fsf7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d87_fsf7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-follow-fill" {...props}></Icon>
