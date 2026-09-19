<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oczhvxbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oczhvxbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:volvo" {...props}></Icon>
